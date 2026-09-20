<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5ctefb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5ctefb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:assignment-user-filled" /></template>
