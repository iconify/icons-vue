<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvuvw1xmg.css';
import '../../css/d/d8pcrprmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nvuvw1xmg"/><path class="d8pcrprmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:clipboard-alt-outline" /></template>
