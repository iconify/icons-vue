<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wokc7ybal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wokc7ybal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:announcement-alt-02" /></template>
