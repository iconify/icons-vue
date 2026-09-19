<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eref7llez.css';
import '../../css/b/bxv5csb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eref7llez"/><path class="bxv5csb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chevrons-right" /></template>
