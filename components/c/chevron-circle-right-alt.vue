<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb6wl9bmp.css';
import '../../css/b/b56j2525l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kb6wl9bmp"/><path class="b56j2525l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chevron-circle-right-alt" /></template>
