<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6b6mob6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6b6mob6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:blood-drop-plus-filled" /></template>
