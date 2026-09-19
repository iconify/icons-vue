<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/f6q5qubpi.css';
import '../../css/z/zpwt154-d.css';
import '../../css/w/wyuzrqbuz.css';
import '../../css/q/qtcublb3e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGizOVze8k"><g class="aql7dnt-u"><path class="f6q5qubpi"/><path class="zpwt154-d"/><path class="wyuzrqbuz"/><path class="qtcublb3e"/></g></mask></defs><path mask="url(#SVGizOVze8k)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:file-lock" /></template>
