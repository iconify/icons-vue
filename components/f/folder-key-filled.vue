<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw4bdbblf.css';
import '../../css/i/i2s-32vgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw4bdbblf"/><path class="i2s-32vgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-key-filled" /></template>
