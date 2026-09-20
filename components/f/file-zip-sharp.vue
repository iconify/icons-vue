<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swa786bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swa786bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-zip-sharp" /></template>
