<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rokf6mb-k.css';
import '../../css/r/r875-hb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rokf6mb-k"/><path clip-rule="evenodd" class="r875-hb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:arrow-right-outline" /></template>
