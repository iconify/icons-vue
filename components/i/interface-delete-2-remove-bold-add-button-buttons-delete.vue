<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sehyrpkys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="sehyrpkys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-delete-2-remove-bold-add-button-buttons-delete" /></template>
