<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9148sb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9148sb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-center-line" /></template>
