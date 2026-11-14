<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cxmd3fufi"/><path class="emwvvt7of"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-minor" /></template>
<style>
.cxmd3fufi {
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.emwvvt7of {
  d: path("M7.5 3.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm6.5 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM5.015 14.61Q5 14.805 5 15q0 .694.185 1.371q.185.676.546 1.298m1.378 1.623q.242.203.506.385t.548.341t.583.294t.613.245t.639.192q.324.083.657.139q.332.056.669.084T12 21q.342 0 .682-.029q.34-.028.675-.085q.336-.057.663-.141q.327-.085.643-.196q.316-.112.618-.249t.587-.299t.55-.347t.508-.391m1.365-1.632q.35-.615.529-1.281T19 15q0-.163-.01-.326m-3.165-4.699q-.425-.237-.884-.42q-.46-.182-.946-.306t-.987-.186T12 9q-.511 0-1.017.064q-.506.063-.996.189t-.953.312t-.89.427m3.152 8.941Q11.645 19 12 19q.365 0 .723-.07m1.118-6.947q-.422-.238-.89-.36q-.467-.123-.951-.123q-.472 0-.93.117t-.872.344m2.92 1.721c-.218-.351-.618-.48-1.118-.432c-.501-.039-.876.108-1.078.404m.207 1.141c.434.237 1.146.321 1.624.613m-.079 1.738a1.36 1.36 0 0 1-.674.104a1.44 1.44 0 0 1-.737-.103M12 12.5v.75m0 4V18m-6.5-6.25c2 .75 3 2.25 3 4.75m10-4.75c-2 .75-3 2.25-3 4.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
