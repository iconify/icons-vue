<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czpeh31ty.css';
import '../../css/t/t5jlxaboc.css';
import '../../css/k/k4a7g7bap.css';
import '../../css/w/w9i3xxbev.css';
import '../../css/z/z16x9fbjm.css';
import '../../css/e/e31xt_wcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czpeh31ty"/><path class="t5jlxaboc"/><path class="k4a7g7bap"/><path class="w9i3xxbev"/><path class="z16x9fbjm"/><path class="e31xt_wcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:diploma-bold-duotone" /></template>
