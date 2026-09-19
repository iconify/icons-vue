<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/n/ndb7b7lyp.css';
import '../../css/i/irjg5qw9q.css';
import '../../css/g/gxdryjbrf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGsMf0tWZq"><g class="aql7dnt-u"><path class="ndb7b7lyp"/><path class="irjg5qw9q"/><path class="gxdryjbrf"/></g></mask></defs><path mask="url(#SVGsMf0tWZq)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:add-item" /></template>
