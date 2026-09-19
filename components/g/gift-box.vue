<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/f694ycdso.css';
import '../../css/w/wtg9n8boz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjL7PiedM"><g class="aql7dnt-u"><path class="f694ycdso"/><path class="wtg9n8boz"/></g></mask></defs><path mask="url(#SVGjL7PiedM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:gift-box" /></template>
