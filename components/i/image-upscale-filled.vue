<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df_472xle.css';
import '../../css/l/l3uet_-9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="df_472xle"/><path class="l3uet_-9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:image-upscale-filled" /></template>
