<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pve6rn_8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pve6rn_8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-plus" /></template>
