<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz8c3l5-w.css';
import '../../css/k/kel-qrbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz8c3l5-w"/><path class="kel-qrbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-minus-duotone" /></template>
