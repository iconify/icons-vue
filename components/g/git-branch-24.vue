<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwsh51bpk.css';
import '../../css/u/ungwd2b5z.css';
import '../../css/r/rj032db8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwsh51bpk"/><path class="ungwd2b5z"/><path class="rj032db8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-branch-24" /></template>
