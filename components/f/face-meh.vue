<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar7nh3bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar7nh3bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-meh" /></template>
