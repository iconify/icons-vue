<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsp48lb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gsp48lb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-in-outline" /></template>
