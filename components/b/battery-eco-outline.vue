<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd2c1ndht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd2c1ndht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-eco-outline" /></template>
