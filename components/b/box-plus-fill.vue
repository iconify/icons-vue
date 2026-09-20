<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plzwab3-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plzwab3-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-plus-fill" /></template>
