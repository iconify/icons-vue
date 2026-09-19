<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvb9twb3e.css';
import '../../css/q/q0sfd_b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvb9twb3e"/><path class="q0sfd_b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:gps" /></template>
