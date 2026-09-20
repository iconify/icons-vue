<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciut39q6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciut39q6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:folder-one" /></template>
