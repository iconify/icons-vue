<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2u47pbtq.css';
import '../../css/p/pdguunnht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f2u47pbtq"/><path class="pdguunnht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:data-boolean-light" /></template>
