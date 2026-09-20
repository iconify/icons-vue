<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/retj535lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="retj535lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevrons-down-right-solid" /></template>
