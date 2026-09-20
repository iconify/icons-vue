<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilmaedj5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilmaedj5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-double-right" /></template>
