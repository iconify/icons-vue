<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sebzf9cjk.css';
import '../../css/u/ujddx7bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sebzf9cjk"/><path class="ujddx7bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-data" /></template>
