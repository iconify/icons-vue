<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/f6q5qubpi.css';
import '../../css/l/lacm7r0qo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGD93INdFk"><g class="aql7dnt-u"><path class="f6q5qubpi"/><path class="lacm7r0qo"/></g></mask></defs><path mask="url(#SVGD93INdFk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:file-hash" /></template>
