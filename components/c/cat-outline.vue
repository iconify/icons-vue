<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnluy6pil.css';
import '../../css/b/bgpfsd5wd.css';
import '../../css/b/bmq6w9aab.css';
import '../../css/l/lmovn-nth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wnluy6pil"/><path class="bgpfsd5wd"/><path class="bmq6w9aab"/><path clip-rule="evenodd" class="lmovn-nth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cat-outline" /></template>
