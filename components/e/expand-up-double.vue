<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5iqhbb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5iqhbb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-up-double" /></template>
