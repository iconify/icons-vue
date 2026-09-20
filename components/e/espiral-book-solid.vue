<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq3zk27rk.css';
import '../../css/h/hlp216lkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq3zk27rk"/><path class="hlp216lkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:espiral-book-solid" /></template>
