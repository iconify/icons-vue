<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl46o5-4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-read-play-outline-rounded" /></template>
<style>
.rl46o5-4u {
  fill: currentColor;
  d: path("m10.944 12.456l2.92-1.946q.272-.187.272-.51t-.272-.51l-2.92-1.946q-.298-.211-.621-.037T10 8.054v3.892q0 .373.323.547t.621-.037M6.077 17l-1.704 1.704q-.379.379-.876.174T3 18.133V4.616q0-.691.463-1.153T4.616 3h14.769q.69 0 1.153.463T21 4.616v10.769q0 .69-.462 1.153T19.385 17zm-.427-1h13.735q.23 0 .423-.192t.192-.423V4.615q0-.23-.192-.423T19.385 4H4.615q-.23 0-.423.192T4 4.615v13.03zM4 16V4z");
}

</style>
