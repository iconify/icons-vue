<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liar723_x.css';
import '../../css/e/e85963y7t.css';
import '../../css/b/blqbp4b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="liar723_x"/><path class="e85963y7t"/><path class="blqbp4b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:email-mail-open-address" /></template>
