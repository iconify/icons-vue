<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfoaij8re.css';
import '../../css/h/hkohktbym.css';
import '../../css/q/q-k3xvb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfoaij8re"/><path class="hkohktbym"/><path class="q-k3xvb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-file-doc" /></template>
