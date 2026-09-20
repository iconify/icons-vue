<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwric7s3u.css';
import '../../css/c/cg9u3_5pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwric7s3u"/><path class="cg9u3_5pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:amusement-park-ferris-wheel-bold" /></template>
