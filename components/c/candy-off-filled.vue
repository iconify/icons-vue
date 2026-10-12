<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyv0rce4w.css';
import '../../css/m/m5_8ni9aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iyv0rce4w"/><path class="m5_8ni9aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:candy-off-filled" /></template>
