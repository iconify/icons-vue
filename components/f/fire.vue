<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bztwfrbon.css';
import '../../css/p/pb328ubdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bztwfrbon"/><path class="pb328ubdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:fire" /></template>
