<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyospdzkg.css';
import '../../css/n/nrwfs8b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyospdzkg"/><path class="nrwfs8b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:badge-dollar" /></template>
