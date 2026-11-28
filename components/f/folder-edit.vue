<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn5l7jbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn5l7jbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-edit" /></template>
