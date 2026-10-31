<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_3ad4bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_3ad4bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-edit-corner-round" /></template>
