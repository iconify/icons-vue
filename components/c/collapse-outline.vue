<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql9ho9wwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ql9ho9wwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:collapse-outline" /></template>
