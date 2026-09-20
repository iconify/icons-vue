<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc1ciyp0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc1ciyp0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:knife-blood-fill" /></template>
