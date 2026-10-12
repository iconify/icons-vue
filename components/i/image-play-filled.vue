<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tst_x0jpw.css';
import '../../css/t/twmjonw6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tst_x0jpw"/><path clip-rule="evenodd" class="twmjonw6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:image-play-filled" /></template>
