<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/o/ooefdb7zl.css';
import '../../css/j/jasl4d3jm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6gpXUYuA"><g class="aql7dnt-u"><path class="ooefdb7zl"/><path class="jasl4d3jm"/></g></mask></defs><path mask="url(#SVG6gpXUYuA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:banana" /></template>
