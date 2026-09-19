<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijzxdu85o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ijzxdu85o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-elbow-up-left" /></template>
