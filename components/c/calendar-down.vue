<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfj01pw_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfj01pw_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:calendar-down" /></template>
