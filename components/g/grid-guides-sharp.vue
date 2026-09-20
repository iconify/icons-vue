<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf6lyuzty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grid-guides-sharp" /></template>
<style>
.jf6lyuzty {
  fill: currentColor;
  d: path("M5.689 19h12.598l-2.773-2.773q-.725.602-1.613.938q-.887.335-1.901.335t-1.901-.338t-1.612-.94zM5 18.287l2.773-2.773q-.602-.725-.937-1.613Q6.5 13.014 6.5 12t.339-1.901t.94-1.612L5 5.688zm3.492-3.493l2.8-2.794l-2.8-2.794q-.467.585-.73 1.286T7.5 12t.263 1.508t.73 1.286m5.015 1.443q.702-.262 1.286-.73L12 12.69l-2.82 2.819q.586.467 1.3.73T12 16.5t1.508-.262M12 11.287l2.794-2.795q-.585-.467-1.286-.73T12 7.5t-1.508.263t-1.286.73zm3.508 3.507q.467-.585.73-1.286T16.5 12t-.262-1.52t-.73-1.3l-2.794 2.795zM19 18.286V5.69l-2.779 2.797q.602.725.94 1.613T17.5 12t-.335 1.901t-.938 1.613zM15.514 7.78L18.312 5H5.713l2.774 2.773q.724-.602 1.612-.937Q10.986 6.5 12 6.5t1.901.339t1.613.94M4 20V4h16v16z");
}

</style>
