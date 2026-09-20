<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8q9e4bsf.css';
import '../../css/m/mgi81ojmu.css';
import '../../css/n/nyrfs3b7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8q9e4bsf"/><circle class="mgi81ojmu"/><circle class="nyrfs3b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:android" /></template>
