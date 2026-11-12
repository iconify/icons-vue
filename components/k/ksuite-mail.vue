<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfjxzhuch.css';
import '../../css/g/gee3w9bni.css';
import '../../css/b/b7vxt34gn.css';
import '../../css/k/kdivkab0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bfjxzhuch"/><path class="gee3w9bni"/><path class="b7vxt34gn"/><path class="kdivkab0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-mail" /></template>
