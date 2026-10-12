<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_r9uibzg.css';
import '../../css/g/gbd4jm86s.css';
import '../../css/z/zc_h-6bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_r9uibzg"/><path class="gbd4jm86s"/><path class="zc_h-6bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-check-filled" /></template>
