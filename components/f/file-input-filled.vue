<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw_jelzmb.css';
import '../../css/l/l_fae7rzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw_jelzmb"/><path class="l_fae7rzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-input-filled" /></template>
