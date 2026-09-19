<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5qqsfbyd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGA4mOJdqT"><path class="n5qqsfbyd"/></mask></defs><path mask="url(#SVGA4mOJdqT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:components" /></template>
