<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gttxmhbqp.css';
import '../../css/p/pa47kd49e.css';
import '../../css/s/skxbewbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gttxmhbqp"/><path class="pa47kd49e"/><path clip-rule="evenodd" class="skxbewbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-music-bold" /></template>
