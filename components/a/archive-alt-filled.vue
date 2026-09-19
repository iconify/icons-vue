<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9e7f6pqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9e7f6pqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:archive-alt-filled" /></template>
