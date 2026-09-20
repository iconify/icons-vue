<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn4spobzw.css';
import '../../css/g/gu1h78e1r.css';
import '../../css/b/bx3clim8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":103,"height":24};
const content = `<path class="kn4spobzw"/><path class="gu1h78e1r"/><path class="bx3clim8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:lockup-github-24" /></template>
