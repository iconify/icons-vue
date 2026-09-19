<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/s/s5vqc5btn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUHJQRchC"><g class="wwvp95byt"><rect class="g47cb4b4t"/><path class="s5vqc5btn"/></g></mask></defs><path mask="url(#SVGUHJQRchC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:add-subtract" /></template>
