<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzug-_pza.css';
import '../../css/p/pknasvape.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzug-_pza"/><path class="pknasvape"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:explore-solid" /></template>
