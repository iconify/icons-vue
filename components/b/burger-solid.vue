<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biljftzdn.css';
import '../../css/c/cg2ro0qum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biljftzdn"/><path clip-rule="evenodd" class="cg2ro0qum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:burger-solid" /></template>
