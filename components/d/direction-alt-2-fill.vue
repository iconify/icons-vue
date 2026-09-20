<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izdje66kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="izdje66kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:direction-alt-2-fill" /></template>
