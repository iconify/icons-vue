<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi4tymrtz.css';
import '../../css/k/k51gsefpd.css';
import '../../css/u/u1wdaq6xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi4tymrtz"/><path clip-rule="evenodd" class="k51gsefpd"/><path clip-rule="evenodd" class="u1wdaq6xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:emoji-joy-light" /></template>
