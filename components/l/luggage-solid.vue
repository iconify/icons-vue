<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oki7nw3lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oki7nw3lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:luggage-solid" /></template>
