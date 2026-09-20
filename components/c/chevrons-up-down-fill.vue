<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnu8uibvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnu8uibvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-up-down-fill" /></template>
