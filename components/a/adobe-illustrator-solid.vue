<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imiobx9sm.css';
import '../../css/k/k4-_ilboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imiobx9sm"/><path clip-rule="evenodd" class="k4-_ilboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:adobe-illustrator-solid" /></template>
