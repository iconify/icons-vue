<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fat3zh_ka.css';
import '../../css/p/pj0wk54iz.css';
import '../../css/p/pzqhllcuo.css';
import '../../css/b/b2v1umb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fat3zh_ka"/><path class="pj0wk54iz"/><path class="pzqhllcuo"/><path class="b2v1umb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:discopanel" /></template>
