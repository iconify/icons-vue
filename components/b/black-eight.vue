<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylrso7y3c.css';
import '../../css/v/vkcj4bcdm.css';
import '../../css/i/iue2exw6u.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGb3Ludd4g"><g class="ylrso7y3c"><path class="vkcj4bcdm"/><path class="iue2exw6u"/></g></mask></defs><path mask="url(#SVGb3Ludd4g)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:black-eight" /></template>
