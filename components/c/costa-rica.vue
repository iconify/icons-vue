<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w37u6nj1g.css';
import '../../css/f/ft6yuqb7o.css';
import '../../css/l/l8fjmsy3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="w37u6nj1g"/><path class="ft6yuqb7o"/><path class="l8fjmsy3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:costa-rica" /></template>
