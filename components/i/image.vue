<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnvj0fsqr.css';
import '../../css/k/kqkvu1bgm.css';
import '../../css/c/c4zydxb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnvj0fsqr"/><path class="kqkvu1bgm"/><path class="c4zydxb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image" /></template>
