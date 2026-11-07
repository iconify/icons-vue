<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4z1ldb0q.css';
import '../../css/o/oj6gwrmjs.css';
import '../../css/g/gvp-p5blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4z1ldb0q"/><path clip-rule="evenodd" class="oj6gwrmjs"/><path class="gvp-p5blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-audio-bold-duotone" /></template>
