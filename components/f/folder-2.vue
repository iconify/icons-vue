<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i12vpz_eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i12vpz_eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:folder-2" /></template>
