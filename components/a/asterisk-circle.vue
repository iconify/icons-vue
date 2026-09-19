<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo1nfcbjg.css';
import '../../css/h/hgfnzqd-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yo1nfcbjg"/><path class="hgfnzqd-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:asterisk-circle" /></template>
