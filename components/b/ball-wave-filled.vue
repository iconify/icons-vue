<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsbbbdb0k.css';
import '../../css/w/w6m22iv5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsbbbdb0k"/><path clip-rule="evenodd" class="w6m22iv5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ball-wave-filled" /></template>
