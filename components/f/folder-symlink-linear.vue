<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_dv9cbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_dv9cbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-symlink-linear" /></template>
