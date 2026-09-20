<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r74_oja1e.css';
import '../../css/d/d267sib8p.css';
import '../../css/w/w13gqbpqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r74_oja1e"/><path class="d267sib8p"/><path class="w13gqbpqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:instagram" /></template>
