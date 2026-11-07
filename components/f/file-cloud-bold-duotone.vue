<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgd8bzbml.css';
import '../../css/e/ey6plua8r.css';
import '../../css/x/x4f46-b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgd8bzbml"/><path class="ey6plua8r"/><path class="x4f46-b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-cloud-bold-duotone" /></template>
