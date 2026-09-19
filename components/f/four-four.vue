<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlbfa8bqm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGl2MrYbix"><path class="vlbfa8bqm"/></mask></defs><path mask="url(#SVGl2MrYbix)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:four-four" /></template>
