<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgd8bzbml.css';
import '../../css/q/qxh6zf45v.css';
import '../../css/b/bk9fnabkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgd8bzbml"/><path class="qxh6zf45v"/><path class="bk9fnabkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-remove-bold-duotone" /></template>
