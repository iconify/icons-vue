<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs0y50bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs0y50bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:infinity" /></template>
