<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfs3dk6ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfs3dk6ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:clipboard-fill" /></template>
