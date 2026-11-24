<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niy3wwbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="niy3wwbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cap-filled" /></template>
