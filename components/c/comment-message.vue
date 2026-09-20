<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjj4o5bfd.css';
import '../../css/q/q9l_p2d0k.css';
import '../../css/l/luprff94i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjj4o5bfd"/><path class="q9l_p2d0k"/><path class="luprff94i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:comment-message" /></template>
