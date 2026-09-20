<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whoue71nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whoue71nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:birthday-2-line" /></template>
