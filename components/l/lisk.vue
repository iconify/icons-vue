<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4ukchbsd.css';
import '../../css/p/pj2uctt-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4ukchbsd"/><path class="pj2uctt-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lisk" /></template>
