<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbg83l2tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":444,"height":512};
const content = `<path clip-rule="evenodd" class="nbg83l2tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:acre" /></template>
