<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c_5tmtm1a"/><path class="ydmhzfbpu"/><path class="e84ffbb5i"/><path class="akqy5y8oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:last-track-button" /></template>
<style>
.akqy5y8oj {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M39.7 12.86c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.327 4.621-2.427 11.421c0 4.8.593 7.3 2.5 7.3c2.542 0 2.827-4.021 5.627-8.421c5.4-8.7 18.9-8.6 18.9-11.6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.c_5tmtm1a {
  fill: var(--svg-color--427687, #427687);
  d: path("M116 3.96H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8v-104c0-4.42-3.58-8-8-8");
}

.e84ffbb5i {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M107.5 63.96v-25.7c0-1.8-1.7-2.9-3-2l-35 24.4v-22.4c.13-1.13-.69-2.15-1.82-2.28c-.45-.05-.9.05-1.28.28l-36.9 25.1v-23.5a1.9 1.9 0 0 0-1.9-1.9H17.4a1.9 1.9 0 0 0-1.9 1.9v52.3c0 1.05.85 1.9 1.9 1.9h10.3a1.9 1.9 0 0 0 1.9-1.9v-23.6l36.9 25c.98.58 2.24.26 2.82-.72c.23-.39.33-.84.28-1.28v-22.3l35 24.4c1.4.9 3-.2 3-2z");
}

.ydmhzfbpu {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M109.7 3.96H11.5a7.555 7.555 0 0 0-7.5 7.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.46c.09-4.05-3.13-7.41-7.18-7.5z");
}

</style>
