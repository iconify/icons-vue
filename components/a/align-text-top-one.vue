<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/i/izdv1gbpk.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG87XrIe9u"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="izdv1gbpk"/></g></mask></defs><path mask="url(#SVG87XrIe9u)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:align-text-top-one" /></template>
