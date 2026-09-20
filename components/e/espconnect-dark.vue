<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etg9crbrk.css';
import '../../css/x/x2l7nqbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="etg9crbrk"/><path class="x2l7nqbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:espconnect-dark" /></template>
