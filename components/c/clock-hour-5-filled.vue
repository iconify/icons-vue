<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvox8lb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvox8lb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clock-hour-5-filled" /></template>
