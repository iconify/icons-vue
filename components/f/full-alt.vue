<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilpm5tagc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilpm5tagc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:full-alt" /></template>
