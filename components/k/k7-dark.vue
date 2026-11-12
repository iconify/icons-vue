<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw16std-u.css';
import '../../css/u/ud-8v13el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iw16std-u"/><path class="ud-8v13el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:k7-dark" /></template>
