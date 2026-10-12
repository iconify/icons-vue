<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_88a0exd.css';
import '../../css/n/np_ttjutp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_88a0exd"/><path clip-rule="evenodd" class="np_ttjutp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cooking-pot-filled" /></template>
