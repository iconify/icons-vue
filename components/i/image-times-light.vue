<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwd_1frdz.css';
import '../../css/b/bcr3mblqh.css';
import '../../css/y/yekhwhkwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qwd_1frdz"/><path class="bcr3mblqh"/><path class="yekhwhkwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-times-light" /></template>
