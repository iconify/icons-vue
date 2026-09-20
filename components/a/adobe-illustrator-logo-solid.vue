<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjn48nb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zjn48nb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-illustrator-logo-solid" /></template>
