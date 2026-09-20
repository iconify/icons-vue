<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-zhl_bfp.css';
import '../../css/y/ytcirkb0g.css';
import '../../css/y/yekhwhkwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-zhl_bfp"/><path class="ytcirkb0g"/><path class="yekhwhkwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-minus-light" /></template>
