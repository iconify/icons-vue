<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gahn9tbab.css';
import '../../css/r/rpqiizbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gahn9tbab"/><path class="rpqiizbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:brain-off-filled" /></template>
