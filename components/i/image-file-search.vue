<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_600mvup.css';
import '../../css/b/bhngwdwnp.css';
import '../../css/t/t26w6qbaq.css';
import '../../css/l/lf0xgxbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_600mvup"/><path class="bhngwdwnp"/><path class="t26w6qbaq"/><path class="lf0xgxbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:image-file-search" /></template>
