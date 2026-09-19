<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/a/anc4d4b1i.css';
import '../../css/w/w3iaqtbfj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGh3ITEBGD"><g class="aql7dnt-u"><path class="anc4d4b1i"/><path class="w3iaqtbfj"/></g></mask></defs><path mask="url(#SVGh3ITEBGD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:chef-hat" /></template>
