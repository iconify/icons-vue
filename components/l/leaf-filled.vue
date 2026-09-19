<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egepqxbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egepqxbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:leaf-filled" /></template>
