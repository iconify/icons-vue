<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puqv5u2-o.css';
import '../../css/n/ngen2gb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puqv5u2-o"/><path class="ngen2gb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-duplicate" /></template>
