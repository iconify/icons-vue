<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfizo7bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kfizo7bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gauge-fill" /></template>
