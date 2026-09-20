<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu71x2f-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu71x2f-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lock-access" /></template>
