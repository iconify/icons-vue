<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm6j0-c1z.css';
import '../../css/s/s9jco_ufp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm6j0-c1z"/><path clip-rule="evenodd" class="s9jco_ufp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:instagram-solid" /></template>
