<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be-x2lgok.css';
import '../../css/j/j0991s5ot.css';
import '../../css/d/daxtkab1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be-x2lgok"/><path clip-rule="evenodd" class="j0991s5ot"/><path clip-rule="evenodd" class="daxtkab1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:instagram-outline" /></template>
